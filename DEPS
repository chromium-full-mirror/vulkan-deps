# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '32238786c835d237c729375f96218e834ab83787',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '5ce04fabf196c57af002e1d6fbdb2f1e339a89d1',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '0d25db97cb9b8f725e4c95e4553001710e7fc39d',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '47c74f488bad1136559f382ce99e8e52d7a392cd',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'b51f6b865c18fc5b33990d12f75e8dfd672cede6',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'e79aee9626316b71614424b44b939aabe2cbf21d',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '697e22d5d256b29e4d6cdd75b3cd42f1aa634113',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '245b48c522b5375c0acd5377d52bef5e4917f31e',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'c4e132b98dfc7c8a5fb7feb99069be68ede3ea28',
}

deps = {
  'glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
  },

  'lunarg-vulkantools/src': {
    'url': '{chromium_git}/external/github.com/LunarG/VulkanTools@{lunarg_vulkantools_revision}',
  },

  'spirv-cross/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Cross@{spirv_cross_revision}',
  },

  'spirv-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Headers@{spirv_headers_revision}',
  },

  'spirv-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Tools@{spirv_tools_revision}',
  },

  'vulkan-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Headers@{vulkan_headers_revision}',
  },

  'vulkan-loader/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Loader@{vulkan_loader_revision}',
  },

  'vulkan-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Tools@{vulkan_tools_revision}',
  },

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
