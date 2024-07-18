# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '52f68dc6b2a9d017b43161f31f13a6f44636ee7c',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '9bd6f95db3076517205b01300c8d37043c5b2dd3',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'db5a00f8cebe81146cafabf89019674a3c4bf03d',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '4c7e1fa5c3d988cca0e626d359d30b117b9c2822',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'b379292b2ab6df5771ba9870d53cf8b2c9295daf',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '5892ebe2d7505c2238a643288d9a5b2e68784a36',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '53a6ba7c235cbe0b0f3e85e3de6d9070bcfec710',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '9479047902e8031210b1bb33a8850e32b313dd25',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'edcf314e81d9866e783ce55855fd1dc482b263e1',
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
