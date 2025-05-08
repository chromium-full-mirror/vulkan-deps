# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '963588074b26326ff0426c8953c1235213309bdb',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '47ee4dce39b5e8b594ed2e9c9cccd10342949683',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '6d0784e9f1ab92c17eeea94821b2465c14a52be9',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'f06e0f3d2e5acfe4b14e714e4103dd1ccdb237e5',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '9c77de5c3dd216f28e407eec65ed9c0a296c1f74',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'fefd7ed96ef9994f0080dbd078822b07d8637918',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'ba13d38d06830f714a93c5bb159e6e4bacacf0bc',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'be40e67892c83d4752ccfbee7ce690ea88087d2b',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '17cf8188d8b49bafb6c2f8ecede238f8d2dec5bf',
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
