# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'f43df42fe69bb38d43625b53e0706bbee43d74b4',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '192b610c89300a30221b8909bf71dcb12cd3c92d',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'c8ad050fcb29e42a2f57d9f59e97488f465c436d',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '8cf1bf9bb922e33135e6e343a566764015da2dc6',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '89268a6d17fc87003b209a1422c17ab288be99a0',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'a1684e4bd23ab130c5e7c37ab72b07dd541897a9',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'f766b30b2de3ffe2cf6b656d943720882617ec58',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'df2e3581520f36776cd42b9fec3ec4a51ab878ef',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '77b73d33d53b3d963265eab459d686a8ff370412',
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
